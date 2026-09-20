<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8bdc-bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8bdc-bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lock-semi-open" {...props}></Icon>
