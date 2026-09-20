<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc6y9objc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc6y9objc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:football" {...props}></Icon>
