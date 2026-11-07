<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu-cc3sah.css';
import '../../css/h/h026ozlsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu-cc3sah"/><path class="h026ozlsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-left-bold-duotone" {...props}></Icon>
