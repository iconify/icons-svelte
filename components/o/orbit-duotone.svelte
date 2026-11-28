<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpk7p9tnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qpk7p9tnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:orbit-duotone" {...props}></Icon>
