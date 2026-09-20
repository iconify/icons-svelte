<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_fdh8bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_fdh8bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-smile" {...props}></Icon>
