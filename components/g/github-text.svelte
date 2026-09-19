<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q98m4fbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="q98m4fbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:github-text" {...props}></Icon>
