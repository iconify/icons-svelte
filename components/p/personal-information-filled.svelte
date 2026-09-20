<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7owqu6zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7owqu6zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:personal-information-filled" {...props}></Icon>
