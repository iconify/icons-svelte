<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke_6hnbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke_6hnbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-merge-conflict" {...props}></Icon>
