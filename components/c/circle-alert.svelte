<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymujj4bpl.css';
import '../../css/q/qxpha_tbq.css';
import '../../css/f/fuhxmiogs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymujj4bpl"/><circle class="qxpha_tbq"/><path class="fuhxmiogs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-alert" {...props}></Icon>
