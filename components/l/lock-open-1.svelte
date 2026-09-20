<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li8oa0riw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="li8oa0riw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:lock-open-1" {...props}></Icon>
