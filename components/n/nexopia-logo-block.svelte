<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vue9z5odm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vue9z5odm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:nexopia-logo-block" {...props}></Icon>
