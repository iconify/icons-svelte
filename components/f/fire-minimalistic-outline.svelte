<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec2hf9bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec2hf9bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fire-minimalistic-outline" {...props}></Icon>
