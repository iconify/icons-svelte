<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbq427-uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbq427-uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:braintree" {...props}></Icon>
