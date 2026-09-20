<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyapu1bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyapu1bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:barbell" {...props}></Icon>
