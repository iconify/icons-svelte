<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl66i7bqg.css';
import '../../css/c/c903nt__c.css';
import '../../css/t/tawopabjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="c903nt__c"/><path class="tawopabjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-slash-bold-duotone" {...props}></Icon>
