<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzwryeaml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jzwryeaml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ast" {...props}></Icon>
