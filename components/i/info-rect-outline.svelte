<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-iiisbix.css';
import '../../css/b/brwrshb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-iiisbix"/><path clip-rule="evenodd" class="brwrshb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:info-rect-outline" {...props}></Icon>
