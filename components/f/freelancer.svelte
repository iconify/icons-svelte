<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzjycqx2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzjycqx2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freelancer" {...props}></Icon>
