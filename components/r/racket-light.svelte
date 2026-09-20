<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtb4debnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtb4debnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:racket-light" {...props}></Icon>
