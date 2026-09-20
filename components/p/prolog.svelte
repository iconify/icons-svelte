<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdd2fk6kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdd2fk6kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:prolog" {...props}></Icon>
