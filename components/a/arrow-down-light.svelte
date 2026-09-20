<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss7a92bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7a92bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-down-light" {...props}></Icon>
