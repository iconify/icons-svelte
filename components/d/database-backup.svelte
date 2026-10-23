<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sois_5fph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sois_5fph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:database-backup" {...props}></Icon>
