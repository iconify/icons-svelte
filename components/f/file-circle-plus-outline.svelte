<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmg372boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmg372boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-circle-plus-outline" {...props}></Icon>
