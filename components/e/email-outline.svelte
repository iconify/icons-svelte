<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovln3iu4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovln3iu4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:email-outline" {...props}></Icon>
