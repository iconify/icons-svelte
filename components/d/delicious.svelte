<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9chckb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9chckb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:delicious" {...props}></Icon>
