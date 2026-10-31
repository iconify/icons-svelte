<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tii4-acje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tii4-acje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:inbox-arrow-up-solid" {...props}></Icon>
