<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc9rjmb9n.css';
import '../../css/p/p7s3evb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vc9rjmb9n"/><path class="p7s3evb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rectangle-circle-filled" {...props}></Icon>
