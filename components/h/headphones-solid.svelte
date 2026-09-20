<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gae1gb42v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gae1gb42v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-solid" {...props}></Icon>
