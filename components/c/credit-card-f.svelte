<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okta756uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="okta756uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:credit-card-f" {...props}></Icon>
