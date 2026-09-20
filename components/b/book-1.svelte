<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e62wtrb5d.css';
import '../../css/s/sksbtdbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e62wtrb5d"/><path class="sksbtdbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:book-1" {...props}></Icon>
