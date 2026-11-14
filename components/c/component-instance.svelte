<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7iu7f5yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:component-instance" {...props}></Icon>
<style>
:global(.z7iu7f5yz) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.174 9.614l-5.788-5.788Q12 1.44 9.614 3.826L3.826 9.614q-2.386 2.386 0 4.772l5.788 5.788q2.386 2.386 4.772 0l5.788-5.788q2.386-2.386 0-4.772m-6.583-.833l1.628 1.628q.66.659.66 1.591t-.66 1.591l-1.628 1.628q-.659.66-1.591.66t-1.591-.66l-1.628-1.628q-.66-.659-.66-1.591t.66-1.591l1.628-1.628q.659-.66 1.591-.66t1.591.66");
}

</style>
