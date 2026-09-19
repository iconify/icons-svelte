<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovn3_lrud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovn3_lrud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hashtag-alt" {...props}></Icon>
