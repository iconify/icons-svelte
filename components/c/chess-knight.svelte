<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7wgjz_yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7wgjz_yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chess-knight" {...props}></Icon>
