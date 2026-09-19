<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dax_enbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dax_enbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:oral-contraception-pillsx21-24px" {...props}></Icon>
