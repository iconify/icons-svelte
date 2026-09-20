<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un3jorbwb.css';
import '../../css/c/c3h8n4bmg.css';
import '../../css/o/oc50jw6ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="un3jorbwb"/><path class="c3h8n4bmg"/><path clip-rule="evenodd" class="oc50jw6ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:email-attachment-document-solid" {...props}></Icon>
