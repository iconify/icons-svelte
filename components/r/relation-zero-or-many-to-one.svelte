<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6j36zt0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6j36zt0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-many-to-one" {...props}></Icon>
