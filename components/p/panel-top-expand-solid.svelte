<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z05sfdc_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z05sfdc_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:panel-top-expand-solid" {...props}></Icon>
