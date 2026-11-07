<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu-cc3sah.css';
import '../../css/o/oei2zdbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu-cc3sah"/><path class="oei2zdbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-left-up-bold-duotone" {...props}></Icon>
