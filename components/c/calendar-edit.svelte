<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl7z0xbvn.css';
import '../../css/q/q9j5fk79c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl7z0xbvn"/><path class="q9j5fk79c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:calendar-edit" {...props}></Icon>
