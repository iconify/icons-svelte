<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql8p6zoco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql8p6zoco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-navbar-collapse-filled" {...props}></Icon>
