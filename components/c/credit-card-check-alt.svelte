<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0k5ecb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0k5ecb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-check-alt" {...props}></Icon>
