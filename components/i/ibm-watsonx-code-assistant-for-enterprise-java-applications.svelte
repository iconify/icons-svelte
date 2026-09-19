<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6i9drdtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t6i9drdtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watsonx-code-assistant-for-enterprise-java-applications" {...props}></Icon>
