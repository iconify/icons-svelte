<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8dq-qb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8dq-qb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-record-filled" {...props}></Icon>
