<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrrzo_bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrrzo_bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-quarter-alt" {...props}></Icon>
