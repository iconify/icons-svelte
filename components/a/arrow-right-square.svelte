<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kem15ubgm.css';
import '../../css/j/jor-usn7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kem15ubgm"/><path class="jor-usn7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-right-square" {...props}></Icon>
