<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo51enbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wo51enbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:globe-alt-01-filled" {...props}></Icon>
