<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq9q0tbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq9q0tbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:at-sign" {...props}></Icon>
