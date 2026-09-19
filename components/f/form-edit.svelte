<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-wq09z1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-wq09z1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:form-edit" {...props}></Icon>
