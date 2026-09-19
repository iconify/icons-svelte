<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn5eqbb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn5eqbb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-next-link" {...props}></Icon>
