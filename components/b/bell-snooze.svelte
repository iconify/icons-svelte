<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m80yxdb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m80yxdb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-snooze" {...props}></Icon>
