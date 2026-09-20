<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q46jpx5lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q46jpx5lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:array-light" {...props}></Icon>
