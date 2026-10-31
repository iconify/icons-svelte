<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg5mpc1ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lg5mpc1ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-boxes-solid" {...props}></Icon>
