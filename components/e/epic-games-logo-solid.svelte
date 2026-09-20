<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvu19abye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvu19abye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:epic-games-logo-solid" {...props}></Icon>
