<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxpwfx6sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yxpwfx6sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-vault-dark" {...props}></Icon>
