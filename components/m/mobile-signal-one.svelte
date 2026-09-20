<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmf6dbc6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmf6dbc6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mobile-signal-one" {...props}></Icon>
