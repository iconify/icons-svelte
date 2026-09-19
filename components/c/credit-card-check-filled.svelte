<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk9e7vb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dk9e7vb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-check-filled" {...props}></Icon>
