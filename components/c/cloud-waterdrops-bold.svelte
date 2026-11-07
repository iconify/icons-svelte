<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s605fxbhp.css';
import '../../css/f/fvrnvdc0s.css';
import '../../css/n/neb4kjwuq.css';
import '../../css/t/tbmfh8b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s605fxbhp"/><path class="fvrnvdc0s"/><path class="neb4kjwuq"/><path class="tbmfh8b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-waterdrops-bold" {...props}></Icon>
