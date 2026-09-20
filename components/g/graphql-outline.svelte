<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c56_ombfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c56_ombfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:graphql-outline" {...props}></Icon>
