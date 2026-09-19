<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6agpcbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w6agpcbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-edit-filled" {...props}></Icon>
