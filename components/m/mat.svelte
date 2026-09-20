<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf83xubvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pf83xubvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:mat" {...props}></Icon>
