<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo382tbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo382tbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-right" {...props}></Icon>
