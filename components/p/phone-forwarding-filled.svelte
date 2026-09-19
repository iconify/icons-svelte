<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-_0twbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-_0twbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-forwarding-filled" {...props}></Icon>
