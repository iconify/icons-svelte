<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p74y-9bqn.css';
import '../../css/d/d_twzvgsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p74y-9bqn"/><path class="d_twzvgsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:plus-square" {...props}></Icon>
