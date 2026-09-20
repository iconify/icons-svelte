<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzbox8agt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="zzbox8agt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:layout" {...props}></Icon>
