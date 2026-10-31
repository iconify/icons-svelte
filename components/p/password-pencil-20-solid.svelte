<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqof0hp_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dqof0hp_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-pencil-20-solid" {...props}></Icon>
