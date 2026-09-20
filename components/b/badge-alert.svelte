<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1g40kz8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1g40kz8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-alert" {...props}></Icon>
