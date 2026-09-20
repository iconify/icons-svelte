<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8qxc_mtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8qxc_mtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chef-hat-filled" {...props}></Icon>
