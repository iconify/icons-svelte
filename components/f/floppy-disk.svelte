<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg80gw99l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg80gw99l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:floppy-disk" {...props}></Icon>
