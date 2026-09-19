<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/locm-c1zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="locm-c1zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-ease-in-filled" {...props}></Icon>
