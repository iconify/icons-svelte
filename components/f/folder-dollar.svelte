<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hphrpobtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hphrpobtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-dollar" {...props}></Icon>
