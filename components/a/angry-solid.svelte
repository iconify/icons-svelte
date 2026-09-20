<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h74ufob4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h74ufob4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:angry-solid" {...props}></Icon>
