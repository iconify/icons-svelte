<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp5mkzh9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hp5mkzh9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-east-escape-fill" {...props}></Icon>
