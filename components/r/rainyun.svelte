<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0tkyh-tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0tkyh-tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rainyun" {...props}></Icon>
