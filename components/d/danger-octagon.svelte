<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkwx5ib8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkwx5ib8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-octagon" {...props}></Icon>
