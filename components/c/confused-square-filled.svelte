<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et_gkj67v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="et_gkj67v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:confused-square-filled" {...props}></Icon>
