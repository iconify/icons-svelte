<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfvqembww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tfvqembww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:inbox-arrow-up-20-solid" {...props}></Icon>
