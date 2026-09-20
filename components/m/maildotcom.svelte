<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdpjm0b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdpjm0b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:maildotcom" {...props}></Icon>
