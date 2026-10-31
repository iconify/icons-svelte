<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1oteybxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1oteybxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-alt-round" {...props}></Icon>
