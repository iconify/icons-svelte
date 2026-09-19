<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj_ri-b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_ri-b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:elec-blanket" {...props}></Icon>
