<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x30i7ibvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x30i7ibvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-check-alt-filled" {...props}></Icon>
