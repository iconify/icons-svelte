<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnpzzt4xm.css';
import '../../css/h/hcvvkpbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnpzzt4xm"/><path class="hcvvkpbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dryer" {...props}></Icon>
