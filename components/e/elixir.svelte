<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk_5x50tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk_5x50tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:elixir" {...props}></Icon>
