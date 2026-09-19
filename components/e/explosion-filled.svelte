<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnlmdbcme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnlmdbcme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:explosion-filled" {...props}></Icon>
