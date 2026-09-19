<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__c8zpwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a__c8zpwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:grapes" {...props}></Icon>
