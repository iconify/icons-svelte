<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btxwembdd.css';
import '../../css/x/xx9h8gkna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":5000,"height":1000};
const content = `<path class="btxwembdd"/><path class="xx9h8gkna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amplitude" {...props}></Icon>
