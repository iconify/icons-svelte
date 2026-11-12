<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qed2t9bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qed2t9bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-flame" {...props}></Icon>
