<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gex-ugb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gex-ugb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:diners-club" {...props}></Icon>
