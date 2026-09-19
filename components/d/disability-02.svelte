<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avar3dbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avar3dbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:disability-02" {...props}></Icon>
