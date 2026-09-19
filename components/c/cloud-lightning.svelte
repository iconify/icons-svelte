<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0-xzpt5k.css';
import '../../css/n/nrqatuf6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer p0-xzpt5k"/><path class="duoicon-secondary-layer nrqatuf6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:cloud-lightning" {...props}></Icon>
