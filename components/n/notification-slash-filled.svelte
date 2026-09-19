<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or6rs0b6f.css';
import '../../css/u/ua_yb7b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="ua_yb7b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:notification-slash-filled" {...props}></Icon>
