<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt7khlbia.css';
import '../../css/o/opq0cgqba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt7khlbia"/><path class="opq0cgqba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:arweave" {...props}></Icon>
