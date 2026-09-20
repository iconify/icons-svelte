<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltj29ibgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ltj29ibgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-step-dark" {...props}></Icon>
