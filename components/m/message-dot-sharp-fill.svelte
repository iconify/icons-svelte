<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sql9n1bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sql9n1bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-dot-sharp-fill" {...props}></Icon>
