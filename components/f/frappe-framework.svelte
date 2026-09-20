<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v73ackb9u.css';
import '../../css/u/uwl1pssco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v73ackb9u"/><path class="uwl1pssco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-framework" {...props}></Icon>
