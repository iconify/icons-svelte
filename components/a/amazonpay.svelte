<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vicm16mkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vicm16mkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonpay" {...props}></Icon>
