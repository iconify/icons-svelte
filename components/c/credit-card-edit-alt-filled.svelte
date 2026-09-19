<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl04e0ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl04e0ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-edit-alt-filled" {...props}></Icon>
