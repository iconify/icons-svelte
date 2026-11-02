<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poq28ib5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="poq28ib5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:battery-25-solid" {...props}></Icon>
