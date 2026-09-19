<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhc3jmhfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhc3jmhfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-minus-alt-filled" {...props}></Icon>
