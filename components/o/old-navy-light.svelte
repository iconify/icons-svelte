<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la7hr5__c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="la7hr5__c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:old-navy-light" {...props}></Icon>
