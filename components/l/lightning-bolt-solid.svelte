<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6m28kyyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6m28kyyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:lightning-bolt-solid" {...props}></Icon>
