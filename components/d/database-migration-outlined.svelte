<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdj9rfmtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj9rfmtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:database-migration-outlined" {...props}></Icon>
