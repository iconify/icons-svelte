<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk5vftbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pk5vftbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mobile-clinic-24px" {...props}></Icon>
