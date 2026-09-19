<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnfctchuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnfctchuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:edit-pencil-line-01" {...props}></Icon>
